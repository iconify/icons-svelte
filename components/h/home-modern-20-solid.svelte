<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf1w6ybal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qf1w6ybal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:home-modern-20-solid" {...props}></Icon>
