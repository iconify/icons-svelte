<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf-ujzx2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="wf-ujzx2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gitlab" {...props}></Icon>
