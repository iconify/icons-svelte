<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8j07dwip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n8j07dwip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:app-store-ios" {...props}></Icon>
