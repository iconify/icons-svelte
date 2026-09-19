<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us6b7-d0g.css';
import '../../css/m/m-wnqh6af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="us6b7-d0g"/><path class="m-wnqh6af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:battery-low" {...props}></Icon>
