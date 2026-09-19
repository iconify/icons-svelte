<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8st50b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s8st50b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:customer-service-filled" {...props}></Icon>
