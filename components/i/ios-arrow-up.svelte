<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewu4g9brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewu4g9brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-up" {...props}></Icon>
