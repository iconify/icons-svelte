<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnlyh2k5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="cnlyh2k5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lock" {...props}></Icon>
