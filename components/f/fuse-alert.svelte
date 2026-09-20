<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_rhs3pvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_rhs3pvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fuse-alert" {...props}></Icon>
