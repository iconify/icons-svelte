<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5m7ms6tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5m7ms6tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nogon-dark" {...props}></Icon>
