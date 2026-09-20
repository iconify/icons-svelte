<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5st_wb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="x5st_wb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-center-fill" {...props}></Icon>
