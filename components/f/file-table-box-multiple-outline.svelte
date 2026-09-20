<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tev1h3bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tev1h3bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-table-box-multiple-outline" {...props}></Icon>
