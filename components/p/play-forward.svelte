<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk08gj-bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vk08gj-bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-forward" {...props}></Icon>
