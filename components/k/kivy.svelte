<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1nvl0bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1nvl0bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kivy" {...props}></Icon>
