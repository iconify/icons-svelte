<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0b9nfbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0b9nfbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:gavel" {...props}></Icon>
