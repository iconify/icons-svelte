<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rngmbwozf.css';
import '../../css/o/obx0gf1ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rngmbwozf"/><path class="obx0gf1ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mic" {...props}></Icon>
