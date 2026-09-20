<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt71oo3zh.css';
import '../../css/w/w6v346ini.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/r/r3zdxib9o.css';
import '../../css/v/v7331qb3y.css';
import '../../css/n/nejkym4sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="rt71oo3zh"/><path class="w6v346ini"/><g class="jn8qy4bru"><path class="r3zdxib9o"/><path class="v7331qb3y"/><path class="nejkym4sf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ox" {...props}></Icon>
