<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwps3bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="aiwps3bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calendar-check" {...props}></Icon>
