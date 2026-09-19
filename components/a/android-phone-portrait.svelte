<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh384qk4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh384qk4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-phone-portrait" {...props}></Icon>
