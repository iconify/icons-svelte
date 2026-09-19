<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou9vwqqhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ou9vwqqhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:phoenix-squadron" {...props}></Icon>
