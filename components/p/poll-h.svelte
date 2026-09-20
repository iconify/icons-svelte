<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbhfrjrke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rbhfrjrke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:poll-h" {...props}></Icon>
