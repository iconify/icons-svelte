<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5m8x1bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x5m8x1bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chart-area" {...props}></Icon>
