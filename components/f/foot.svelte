<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2b16wbvz.css';
import '../../css/r/rs61gez4m.css';
import '../../css/l/lmjzrrkso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="b2b16wbvz"/><path class="rs61gez4m"/><path class="lmjzrrkso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:foot" {...props}></Icon>
