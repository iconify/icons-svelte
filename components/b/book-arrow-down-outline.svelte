<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw9ntk0ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw9ntk0ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-down-outline" {...props}></Icon>
