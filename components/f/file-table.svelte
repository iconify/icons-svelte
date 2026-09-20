<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo-fgf_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo-fgf_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-table" {...props}></Icon>
