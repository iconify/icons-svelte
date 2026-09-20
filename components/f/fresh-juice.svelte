<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2cef4b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o2cef4b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:fresh-juice" {...props}></Icon>
