<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7o0qobko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7o0qobko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:planet-sharp" {...props}></Icon>
