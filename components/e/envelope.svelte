<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks644wben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="ks644wben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:envelope" {...props}></Icon>
