<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwt1nfn4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cwt1nfn4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-chevron-up" {...props}></Icon>
