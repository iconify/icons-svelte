<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adb4xn-2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="adb4xn-2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:bell-slash" {...props}></Icon>
