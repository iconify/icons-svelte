<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn2jg20aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="nn2jg20aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:battery-three-quarters" {...props}></Icon>
