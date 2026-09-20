<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4d9-5bmv.css';
import '../../css/m/mad6u8jan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p4d9-5bmv"/><path class="mad6u8jan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-airlines-dark" {...props}></Icon>
