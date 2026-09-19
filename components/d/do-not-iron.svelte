<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewi53ukxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="ewi53ukxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:do-not-iron" {...props}></Icon>
