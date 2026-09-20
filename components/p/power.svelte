<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9n5_yi4d.css';
import '../../css/x/xvcpc4g1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="b9n5_yi4d"/><path class="xvcpc4g1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:power" {...props}></Icon>
