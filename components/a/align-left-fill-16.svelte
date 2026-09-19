<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv97p5bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fv97p5bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-left-fill-16" {...props}></Icon>
