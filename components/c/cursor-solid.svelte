<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbk37tb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbk37tb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cursor-solid" {...props}></Icon>
