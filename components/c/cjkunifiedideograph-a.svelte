<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w25egcbny.css';
import '../../css/e/egmsjwuap.css';
import '../../css/x/xsjsq4bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w25egcbny"/><path class="egmsjwuap"/><path class="xsjsq4bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cjkunifiedideograph-a" {...props}></Icon>
