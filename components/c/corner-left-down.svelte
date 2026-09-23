<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxrv3d63f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxrv3d63f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-left-down" {...props}></Icon>
