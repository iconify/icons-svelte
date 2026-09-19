<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2sb3hbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v2sb3hbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:date-time-12" {...props}></Icon>
