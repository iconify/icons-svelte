<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc9n9eb3h.css';
import '../../css/z/zxnivje1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vc9n9eb3h"/><path class="zxnivje1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heartgreen" {...props}></Icon>
