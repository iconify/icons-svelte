<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb201_2ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fb201_2ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ipcs" {...props}></Icon>
