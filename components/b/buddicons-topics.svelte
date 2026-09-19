<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wupi-6bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wupi-6bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-topics" {...props}></Icon>
