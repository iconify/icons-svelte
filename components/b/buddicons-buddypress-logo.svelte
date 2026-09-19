<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk93trgoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vk93trgoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:buddicons-buddypress-logo" {...props}></Icon>
