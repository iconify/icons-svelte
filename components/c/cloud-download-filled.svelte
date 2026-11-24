<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-jafa0z.css';
import '../../css/e/e9d8alb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl-jafa0z"/><path class="e9d8alb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-download-filled" {...props}></Icon>
