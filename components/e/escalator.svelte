<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfquvsb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yfquvsb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:escalator" {...props}></Icon>
