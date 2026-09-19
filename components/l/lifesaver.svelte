<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f3sakpbgo.css';
import '../../css/z/zbtxb8i9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="f3sakpbgo"/><path class="zbtxb8i9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:lifesaver" {...props}></Icon>
