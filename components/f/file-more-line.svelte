<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmu7ij10d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmu7ij10d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-more-line" {...props}></Icon>
