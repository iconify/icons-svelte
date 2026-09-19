<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq4l7_blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dq4l7_blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mic" {...props}></Icon>
