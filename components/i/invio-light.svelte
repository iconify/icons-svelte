<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spyfq2bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spyfq2bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invio-light" {...props}></Icon>
