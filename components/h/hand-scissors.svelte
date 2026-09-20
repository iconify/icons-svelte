<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od07oia4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="od07oia4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-scissors" {...props}></Icon>
