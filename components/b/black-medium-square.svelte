<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr5lrxbeo.css';
import '../../css/y/y5hdzhbmr.css';
import '../../css/y/yi3irnyqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="pr5lrxbeo"/><path class="y5hdzhbmr"/><path class="yi3irnyqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-medium-square" {...props}></Icon>
