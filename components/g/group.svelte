<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck5l6tb3a.css';
import '../../css/t/tx2p9khav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ck5l6tb3a"/><path class="tx2p9khav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:group" {...props}></Icon>
