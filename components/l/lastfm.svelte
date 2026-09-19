<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5yi_xb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5yi_xb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:lastfm" {...props}></Icon>
