<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh2ydkb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uh2ydkb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-dropup-circle" {...props}></Icon>
