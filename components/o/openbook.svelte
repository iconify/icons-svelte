<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpl09-boe.css';
import '../../css/m/my7pz4ppw.css';
import '../../css/n/ni4k71_hl.css';
import '../../css/w/w-ic5dfog.css';
import '../../css/z/zzhkhubht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tpl09-boe"/><path class="my7pz4ppw"/><path class="ni4k71_hl"/><path class="w-ic5dfog"/><path class="zzhkhubht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:openbook" {...props}></Icon>
