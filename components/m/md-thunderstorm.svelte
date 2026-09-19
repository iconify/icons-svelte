<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrjwib-mi.css';
import '../../css/h/hlu7_ghbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wrjwib-mi"/><path class="hlu7_ghbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-thunderstorm" {...props}></Icon>
