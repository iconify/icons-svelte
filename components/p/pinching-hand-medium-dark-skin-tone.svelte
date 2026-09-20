<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a70p5jbrs.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/p/pfu1jhazf.css';
import '../../css/l/lor9bq23v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a70p5jbrs"/><g class="jn8qy4bru"><path class="pfu1jhazf"/><path class="lor9bq23v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pinching-hand-medium-dark-skin-tone" {...props}></Icon>
