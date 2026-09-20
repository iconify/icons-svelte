<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohhcw2bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ohhcw2bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-exclamation-point" {...props}></Icon>
