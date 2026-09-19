<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbv9h06jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbv9h06jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:phone" {...props}></Icon>
