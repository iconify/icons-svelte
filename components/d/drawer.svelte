<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsp_xm4zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsp_xm4zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:drawer" {...props}></Icon>
