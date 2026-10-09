<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd8a8ccdm.css';
import '../../css/x/x2-lnebmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fd8a8ccdm"/><path class="x2-lnebmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammer-48-bold" {...props}></Icon>
