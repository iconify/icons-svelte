<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9w7clzrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9w7clzrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:activity-20-bold" {...props}></Icon>
