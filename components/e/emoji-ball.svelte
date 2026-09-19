<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nls4zt4jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nls4zt4jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:emoji-ball" {...props}></Icon>
