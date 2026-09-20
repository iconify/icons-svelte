<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or9gezb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="or9gezb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chrome" {...props}></Icon>
