<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_zm7infu.css';
import '../../css/j/jzvydlbca.css';
import '../../css/t/t2jzbtbga.css';
import '../../css/c/clmzz-59m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_zm7infu"/><path class="jzvydlbca"/><path class="t2jzbtbga"/><path class="clmzz-59m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:octopus" {...props}></Icon>
