<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4xhvpc1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4xhvpc1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:joomla-light" {...props}></Icon>
