<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soau7yb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="soau7yb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:drumstick-bite" {...props}></Icon>
