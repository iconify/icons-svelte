<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzkm26lyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hzkm26lyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-blank-stroke-16" {...props}></Icon>
