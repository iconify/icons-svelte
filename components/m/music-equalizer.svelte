<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlzd_xg5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jlzd_xg5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-equalizer" {...props}></Icon>
