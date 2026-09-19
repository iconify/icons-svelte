<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gb1ollb9h.css';
import '../../css/r/rr89zbbbj.css';
import '../../css/j/jcwdig4nw.css';
import '../../css/s/sprzifbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="gb1ollb9h"/><path class="rr89zbbbj"/><path class="jcwdig4nw"/><path class="sprzifbpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:four-leaf-clover" {...props}></Icon>
