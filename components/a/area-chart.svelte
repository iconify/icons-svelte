<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ielrypj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h4ielrypj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:area-chart" {...props}></Icon>
