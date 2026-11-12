<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3_v_u3_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f3_v_u3_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alpine-linux-light" {...props}></Icon>
