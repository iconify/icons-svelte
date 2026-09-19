<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_onf2jax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_onf2jax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:avr" {...props}></Icon>
