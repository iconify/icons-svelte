<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntuzksbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntuzksbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cloth" {...props}></Icon>
