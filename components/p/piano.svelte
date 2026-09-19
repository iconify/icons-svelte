<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhk06ihte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="lhk06ihte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:piano" {...props}></Icon>
