<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o76-z65vg.css';
import '../../css/v/v5zh6_2ok.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/m/mjfrbba7t.css';
import '../../css/t/t02fqreuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="o76-z65vg"/><path class="v5zh6_2ok"/><g class="jn8qy4bru"><path class="mjfrbba7t"/><path class="t02fqreuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ice-shelf" {...props}></Icon>
