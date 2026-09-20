<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juvuk6mdh.css';
import '../../css/f/fi4s-dblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2500,"height":2500};
const content = `<path class="juvuk6mdh"/><path class="fi4s-dblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:npm" {...props}></Icon>
