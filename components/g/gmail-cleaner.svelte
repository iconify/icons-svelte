<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl809_b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl809_b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gmail-cleaner" {...props}></Icon>
