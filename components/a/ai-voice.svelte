<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il8gdxbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il8gdxbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ai-voice" {...props}></Icon>
