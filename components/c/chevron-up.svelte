<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidi1vbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="qidi1vbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chevron-up" {...props}></Icon>
