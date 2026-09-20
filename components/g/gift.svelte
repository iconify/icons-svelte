<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjn-0b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="ufjn-0b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:gift" {...props}></Icon>
