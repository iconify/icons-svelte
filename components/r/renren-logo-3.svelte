<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx_j1xbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx_j1xbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:renren-logo-3" {...props}></Icon>
