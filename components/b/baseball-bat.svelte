<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1yx7eixm.css';
import '../../css/z/zrcrh4bnb.css';
import '../../css/j/jxmh2ibtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="p1yx7eixm"><circle class="zrcrh4bnb"/><path class="jxmh2ibtp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:baseball-bat" {...props}></Icon>
