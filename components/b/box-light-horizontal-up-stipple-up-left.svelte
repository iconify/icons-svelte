<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik9kr5b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ik9kr5b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up-stipple-up-left" {...props}></Icon>
