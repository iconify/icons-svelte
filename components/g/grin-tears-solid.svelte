<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryr9acblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ryr9acblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grin-tears-solid" {...props}></Icon>
