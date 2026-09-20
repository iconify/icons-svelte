<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umm606kxf.css';
import '../../css/g/g10zemb6e.css';
import '../../css/j/jn0k031ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":41,"height":41,"left":-0.5};
const content = `<g class="umm606kxf"><path class="g10zemb6e"/><path class="jn0k031ks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-stickies-color:cursor" {...props}></Icon>
