<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_r3zubbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y_r3zubbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:crosshair" {...props}></Icon>
