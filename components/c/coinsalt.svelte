<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp6xecb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="vp6xecb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:coinsalt" {...props}></Icon>
