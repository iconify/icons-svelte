<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvjhj9bjg.css';
import '../../css/j/jpru1cc9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mvjhj9bjg"/><path class="jpru1cc9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rockylinux-wordmark" {...props}></Icon>
