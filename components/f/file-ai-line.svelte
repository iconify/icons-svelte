<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i63bjac3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i63bjac3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-ai-line" {...props}></Icon>
