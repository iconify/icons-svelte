<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/za8d6-7ga.css';
import '../../css/d/dlev0uh6a.css';
import '../../css/x/x4639o9tv.css';
import '../../css/w/wulhmubft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="za8d6-7ga"/><path class="dlev0uh6a wm-a"/><path class="x4639o9tv"/><path class="wulhmubft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-compare-duo" {...props}></Icon>
