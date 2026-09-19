<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3cy-l8ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3cy-l8ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heavylargecircle" {...props}></Icon>
