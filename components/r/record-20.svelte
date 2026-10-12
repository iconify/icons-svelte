<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd9t-4b_w.css';
import '../../css/v/vixdv7vsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pd9t-4b_w"/><path class="vixdv7vsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:record-20" {...props}></Icon>
