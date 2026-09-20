<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hke8i3ela.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hke8i3ela"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hivemq-light" {...props}></Icon>
