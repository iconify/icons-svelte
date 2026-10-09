<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2eh8bdrp.css';
import '../../css/e/ewna1ybwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2eh8bdrp"/><path class="ewna1ybwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-point-sign-20" {...props}></Icon>
