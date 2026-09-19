<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erzf03bmv.css';
import '../../css/r/rplob1ewi.css';
import '../../css/a/a0910tb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="rplob1ewi"/><path class="a0910tb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:mf-1x1" {...props}></Icon>
