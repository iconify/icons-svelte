<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvsyxl1vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qvsyxl1vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:accountfilter" {...props}></Icon>
