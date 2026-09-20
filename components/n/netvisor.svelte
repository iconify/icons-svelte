<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bun4fvbdj.css';
import '../../css/k/ky_2mwb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bun4fvbdj"/><path class="ky_2mwb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netvisor" {...props}></Icon>
