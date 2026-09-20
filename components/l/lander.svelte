<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo324-b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xo324-b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lander" {...props}></Icon>
