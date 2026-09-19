<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6uuusb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6uuusb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-contrast" {...props}></Icon>
