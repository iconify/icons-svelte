<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxjz801rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxjz801rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dxc" {...props}></Icon>
