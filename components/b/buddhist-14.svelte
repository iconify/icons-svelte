<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc7njrg0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kc7njrg0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:buddhist-14" {...props}></Icon>
