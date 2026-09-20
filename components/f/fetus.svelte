<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj58pwuum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uj58pwuum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fetus" {...props}></Icon>
