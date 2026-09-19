<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv8_5tben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nv8_5tben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-people" {...props}></Icon>
