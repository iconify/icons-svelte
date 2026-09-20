<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv10l8h9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iv10l8h9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kumiho-dark" {...props}></Icon>
