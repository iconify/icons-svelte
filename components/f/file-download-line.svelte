<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n355cfcse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n355cfcse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-download-line" {...props}></Icon>
