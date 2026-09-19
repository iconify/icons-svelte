<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/azt281bjx.css';
import '../../css/c/c2tqwxb8j.css';
import '../../css/x/x2qupdbaz.css';
import '../../css/h/hmpex9bvg.css';
import '../../css/e/e-bh6stpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="azt281bjx"/><rect class="c2tqwxb8j"/><path class="x2qupdbaz"/><circle class="hmpex9bvg"/><circle class="e-bh6stpr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hamburger-one" {...props}></Icon>
