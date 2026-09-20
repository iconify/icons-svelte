<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm8d2ebpn.css';
import '../../css/g/grqo4obbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rm8d2ebpn"/><path class="grqo4obbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:flip-h" {...props}></Icon>
