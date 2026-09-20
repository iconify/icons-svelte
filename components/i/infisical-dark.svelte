<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqvox4byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqvox4byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:infisical-dark" {...props}></Icon>
