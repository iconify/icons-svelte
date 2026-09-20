<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x53po9jgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x53po9jgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-check" {...props}></Icon>
