<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v54shr-2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v54shr-2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:daisy" {...props}></Icon>
