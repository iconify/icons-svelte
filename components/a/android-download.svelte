<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2c0ysb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2c0ysb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-download" {...props}></Icon>
