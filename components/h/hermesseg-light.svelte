<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpn4e3smv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpn4e3smv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hermesseg-light" {...props}></Icon>
