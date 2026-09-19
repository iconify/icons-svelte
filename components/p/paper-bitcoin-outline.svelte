<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/j/j91vxv8id.css';
import '../../css/v/vgqf9ebff.css';
import '../../css/h/hjpx-0bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="j91vxv8id"/><path class="vgqf9ebff"/><path class="hjpx-0bmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:paper-bitcoin-outline" {...props}></Icon>
