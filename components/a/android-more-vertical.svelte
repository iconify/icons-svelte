<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwt5gdbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwt5gdbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-more-vertical" {...props}></Icon>
