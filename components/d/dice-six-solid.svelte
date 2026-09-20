<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6lud-ixf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6lud-ixf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dice-six-solid" {...props}></Icon>
