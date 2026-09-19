<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swmo9bk_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="swmo9bk_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:registered" {...props}></Icon>
