<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj8hsacgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lj8hsacgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pencil-solid" {...props}></Icon>
