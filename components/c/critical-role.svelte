<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kahccmb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kahccmb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:critical-role" {...props}></Icon>
