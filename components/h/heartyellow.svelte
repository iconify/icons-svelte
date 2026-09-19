<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncr9o6bsk.css';
import '../../css/z/zegs8bbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncr9o6bsk"/><path class="zegs8bbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heartyellow" {...props}></Icon>
