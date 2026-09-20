<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3_f46b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_f46b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-alert-outline" {...props}></Icon>
