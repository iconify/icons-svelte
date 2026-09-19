<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g3kpjqbfy.css';
import '../../css/t/tgug5f0tr.css';
import '../../css/w/wmhvhjlfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g3kpjqbfy"/><path class="tgug5f0tr"/><path class="wmhvhjlfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:japanese-congratulations-button" {...props}></Icon>
