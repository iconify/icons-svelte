<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/glkqlxbac.css';
import '../../css/f/fvwt6sbil.css';
import '../../css/g/goklkbcov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="d2kvgvbvc"><path class="glkqlxbac"/><path class="fvwt6sbil"/><path class="goklkbcov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ml-4x3" {...props}></Icon>
