<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcm_16b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcm_16b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-column-decreasing" {...props}></Icon>
