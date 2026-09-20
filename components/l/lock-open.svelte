<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y8ol2mkbg.css';
import '../../css/z/zxhjaubkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 1)" class="bi12bsetm"><path class="y8ol2mkbg"/><circle class="zxhjaubkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:lock-open" {...props}></Icon>
