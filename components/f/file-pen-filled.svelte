<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq7fbvbpx.css';
import '../../css/p/pj3mk0brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7fbvbpx"/><path class="pj3mk0brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-pen-filled" {...props}></Icon>
