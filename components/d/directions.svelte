<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbt-b3b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hbt-b3b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:directions" {...props}></Icon>
