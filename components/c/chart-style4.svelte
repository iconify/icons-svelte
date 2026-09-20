<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik_7hmbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ik_7hmbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:chart-style4" {...props}></Icon>
