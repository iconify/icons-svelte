<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl66i7bqg.css';
import '../../css/d/dz4pyzk-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="cl66i7bqg"/><path class="dz4pyzk-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-check-bold-duotone" {...props}></Icon>
