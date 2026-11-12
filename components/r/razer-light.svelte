<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci8nr7brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ci8nr7brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:razer-light" {...props}></Icon>
