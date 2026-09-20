<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvmtihvpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wvmtihvpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emulatorjs-dark" {...props}></Icon>
