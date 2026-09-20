<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_2ocb6i.css';
import '../../css/z/z1wl8j83j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1_2ocb6i"/><path class="z1wl8j83j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qwik-light" {...props}></Icon>
