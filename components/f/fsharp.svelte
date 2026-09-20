<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrm90vr2z.css';
import '../../css/r/rvlpixg0l.css';
import '../../css/d/dgch7ibmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="lrm90vr2z"/><path class="rvlpixg0l"/><path class="dgch7ibmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:fsharp" {...props}></Icon>
