<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmd3obcfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lmd3obcfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:calendar" {...props}></Icon>
