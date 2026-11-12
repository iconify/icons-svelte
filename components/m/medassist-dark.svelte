<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unm-bsb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unm-bsb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medassist-dark" {...props}></Icon>
