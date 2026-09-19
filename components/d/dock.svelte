<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avst9pwzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":480};
const content = `<path class="avst9pwzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dock" {...props}></Icon>
