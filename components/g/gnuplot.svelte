<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzt8tcrza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16,"top":-16};
const content = `<path class="zzt8tcrza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gnuplot" {...props}></Icon>
