<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lx6sfha5x.css';
import '../../css/q/qz0s-uf3y.css';
import '../../css/b/bukhfnboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="lx6sfha5x"/><path class="qz0s-uf3y"/><path class="bukhfnboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:calendar-3" {...props}></Icon>
