<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tw1okb6_l.css';
import '../../css/b/b33loqboc.css';
import '../../css/y/yu9s21war.css';
import '../../css/j/j002eop6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tw1okb6_l"/><path class="b33loqboc"/><path class="yu9s21war"/><path class="j002eop6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-curve-double-duo" {...props}></Icon>
