<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahk1xk91p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahk1xk91p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:fantasy-flight-games" {...props}></Icon>
