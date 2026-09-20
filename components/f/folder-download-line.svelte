<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibdr8ccft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibdr8ccft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-download-line" {...props}></Icon>
