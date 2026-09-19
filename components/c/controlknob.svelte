<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrmchxbkx.css';
import '../../css/c/ct8h_-63x.css';
import '../../css/i/ix-wrkbcl.css';
import '../../css/g/gt8_c-sxg.css';
import '../../css/n/nvux4rq-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zrmchxbkx"/><path class="ct8h_-63x"/><path class="ix-wrkbcl"/><path class="gt8_c-sxg"/><path class="nvux4rq-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:controlknob" {...props}></Icon>
