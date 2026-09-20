<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji862o97d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji862o97d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kumiho-light" {...props}></Icon>
