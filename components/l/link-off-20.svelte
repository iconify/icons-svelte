<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qff4tsb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qff4tsb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-off-20" {...props}></Icon>
