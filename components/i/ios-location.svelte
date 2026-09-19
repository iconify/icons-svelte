<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpqyh0d1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpqyh0d1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-location" {...props}></Icon>
