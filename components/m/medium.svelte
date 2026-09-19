<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj0wl3bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":12};
const content = `<path class="bj0wl3bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:medium" {...props}></Icon>
