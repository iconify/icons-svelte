<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loedw3efo.css';
import '../../css/f/fas83m7xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="loedw3efo"/><path class="fas83m7xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:robinson" {...props}></Icon>
