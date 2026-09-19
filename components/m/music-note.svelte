<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sicc9-b3w.css';
import '../../css/x/x2mt7mwiz.css';
import '../../css/l/l9xqvz5sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="sicc9-b3w"/><path class="x2mt7mwiz"/><path class="l9xqvz5sp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:music-note" {...props}></Icon>
