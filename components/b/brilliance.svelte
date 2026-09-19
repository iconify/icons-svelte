<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsm32d9mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsm32d9mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:brilliance" {...props}></Icon>
