<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5-0-5bhi.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/m/mp7-b1b3k.css';
import '../../css/i/ixt7oqbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="o5-0-5bhi"/><g class="jn8qy4bru"><path class="mp7-b1b3k"/><path class="ixt7oqbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:back-arrow" {...props}></Icon>
