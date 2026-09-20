<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbqpt1baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbqpt1baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:quote" {...props}></Icon>
