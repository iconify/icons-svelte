<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9j9d9bcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j9j9d9bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-microphone" {...props}></Icon>
