<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p29-zfr-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p29-zfr-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ampl" {...props}></Icon>
