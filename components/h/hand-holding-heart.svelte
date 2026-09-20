<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7elhyu2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z7elhyu2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-holding-heart" {...props}></Icon>
