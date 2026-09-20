<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0xzv1mye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g0xzv1mye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:plug" {...props}></Icon>
