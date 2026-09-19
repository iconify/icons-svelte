<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi_4_2dxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vi_4_2dxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:airline-rapid-board" {...props}></Icon>
