<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th995e03e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="th995e03e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ladder-light" {...props}></Icon>
