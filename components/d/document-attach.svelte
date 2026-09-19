<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kduvb0e1b.css';
import '../../css/q/qbzdmcc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kduvb0e1b"/><path class="qbzdmcc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:document-attach" {...props}></Icon>
