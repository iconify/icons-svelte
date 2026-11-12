<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaztqrg0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jaztqrg0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crt-sh-light" {...props}></Icon>
