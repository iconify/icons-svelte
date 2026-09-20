<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b75n16h0k.css';
import '../../css/l/lb9mvccia.css';
import '../../css/t/t98381bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="b75n16h0k"/><path class="lb9mvccia"/><path class="t98381bax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:message" {...props}></Icon>
