<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj8vw15bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fj8vw15bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:registered" {...props}></Icon>
