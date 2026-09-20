<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/ek_0oyb1o.css';
import '../../css/j/jxyaplgzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(5 3)" class="bi12bsetm"><path class="ek_0oyb1o"/><circle class="jxyaplgzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:iphone-portrait" {...props}></Icon>
