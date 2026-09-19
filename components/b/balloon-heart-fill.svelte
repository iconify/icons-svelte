<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n74l300wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n74l300wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:balloon-heart-fill" {...props}></Icon>
