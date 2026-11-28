<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w48vkb1yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w48vkb1yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-php-light" {...props}></Icon>
