<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3dpzbtra.css';
import '../../css/r/ry3fse1zo.css';
import '../../css/u/ul1worher.css';
import '../../css/l/llqfild5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="ry3fse1zo"/><path class="ul1worher"/><path class="llqfild5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:baokemeng" {...props}></Icon>
