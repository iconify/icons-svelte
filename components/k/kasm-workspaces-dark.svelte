<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m12oh2bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m12oh2bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kasm-workspaces-dark" {...props}></Icon>
