<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvje_n8dl.css';
import '../../css/x/x662ljhor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dvje_n8dl"/><path class="x662ljhor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:erugo-dark" {...props}></Icon>
