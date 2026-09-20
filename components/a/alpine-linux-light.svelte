<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzficqbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jzficqbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alpine-linux-light" {...props}></Icon>
