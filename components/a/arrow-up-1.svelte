<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6kox_6dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l6kox_6dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-up-1" {...props}></Icon>
