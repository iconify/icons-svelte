<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1yx7eixm.css';
import '../../css/a/aoabsmt9b.css';
import '../../css/c/cjjtizl0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="p1yx7eixm"><circle class="aoabsmt9b"/><path class="cjjtizl0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:instagram-one" {...props}></Icon>
