<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j88-bkbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j88-bkbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:music-equalizer" {...props}></Icon>
