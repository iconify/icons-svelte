<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c608p5bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c608p5bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:metro" {...props}></Icon>
