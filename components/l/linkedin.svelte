<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el2y-txid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="el2y-txid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:linkedin" {...props}></Icon>
