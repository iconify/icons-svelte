<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8h3wbbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f8h3wbbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:happy" {...props}></Icon>
