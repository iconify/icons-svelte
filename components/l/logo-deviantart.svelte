<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u208bsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m8u208bsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-deviantart" {...props}></Icon>
