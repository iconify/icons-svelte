<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f56drqufx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f56drqufx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:railway-track-narrow" {...props}></Icon>
