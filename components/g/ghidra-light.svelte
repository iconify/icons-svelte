<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9q3jccrn.css';
import '../../css/m/m920y4n8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k9q3jccrn"/><path class="m920y4n8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghidra-light" {...props}></Icon>
