<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncjysacrn.css';
import '../../css/m/mcrk-8rcw.css';
import '../../css/z/zr763ccpc.css';
import '../../css/z/zeqjldbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ncjysacrn"/><circle class="mcrk-8rcw"/><circle class="zr763ccpc"/><path class="zeqjldbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:middling" {...props}></Icon>
