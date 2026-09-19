<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gg9a5mbfj.css';
import '../../css/p/phqvtfx7h.css';
import '../../css/t/t5rgi3bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gg9a5mbfj"/><path class="phqvtfx7h"/><path class="t5rgi3bje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:layers" {...props}></Icon>
