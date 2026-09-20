<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grq6pustu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="grq6pustu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pushbase" {...props}></Icon>
