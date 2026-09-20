<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k17jsw1bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="k17jsw1bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:layout" {...props}></Icon>
