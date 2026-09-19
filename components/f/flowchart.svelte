<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnciz5-lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rnciz5-lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:flowchart" {...props}></Icon>
