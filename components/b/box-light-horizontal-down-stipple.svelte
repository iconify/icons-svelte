<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdte0c4ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wdte0c4ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-down-stipple" {...props}></Icon>
