<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbhc0x5av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbhc0x5av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-tcx-filled" {...props}></Icon>
