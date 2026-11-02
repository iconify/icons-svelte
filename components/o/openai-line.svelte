<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw80cbc2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw80cbc2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:openai-line" {...props}></Icon>
