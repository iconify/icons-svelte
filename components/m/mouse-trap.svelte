<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_ap_i7do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_ap_i7do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:mouse-trap" {...props}></Icon>
