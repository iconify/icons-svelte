<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6l4-mboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k6l4-mboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:php" {...props}></Icon>
