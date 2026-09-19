<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fkuzt-b3i.css';
import '../../css/c/c0lwb7bgm.css';
import '../../css/k/kiy1bvb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><path class="fkuzt-b3i"/><path class="c0lwb7bgm"/><path class="kiy1bvb5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:multifunction-knife" {...props}></Icon>
