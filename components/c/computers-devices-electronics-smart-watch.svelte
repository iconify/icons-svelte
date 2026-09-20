<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhjs9ibxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhjs9ibxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-smart-watch" {...props}></Icon>
