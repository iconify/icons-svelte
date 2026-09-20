<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg6obmb_i.css';
import '../../css/c/c_7z8eb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":201,"height":201};
const content = `<path class="lg6obmb_i"/><path class="c_7z8eb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:groq" {...props}></Icon>
