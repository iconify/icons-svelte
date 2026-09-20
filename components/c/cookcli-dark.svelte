<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk0k5hb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0k5hb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cookcli-dark" {...props}></Icon>
