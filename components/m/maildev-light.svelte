<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-hw-5bzi.css';
import '../../css/m/mtxmfcb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-hw-5bzi"/><path class="mtxmfcb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maildev-light" {...props}></Icon>
