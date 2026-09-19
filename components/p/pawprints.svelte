<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxlv3ga7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxlv3ga7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pawprints" {...props}></Icon>
