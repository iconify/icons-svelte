<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-h5b6a8z.css';
import '../../css/m/mqn54kwig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t-h5b6a8z"/><path class="mqn54kwig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operational" {...props}></Icon>
