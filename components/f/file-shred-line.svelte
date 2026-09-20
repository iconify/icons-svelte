<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlkp8bqjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlkp8bqjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-shred-line" {...props}></Icon>
