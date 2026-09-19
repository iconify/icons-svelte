<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqp8abb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hqp8abb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:curlyloop" {...props}></Icon>
