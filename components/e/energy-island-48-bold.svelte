<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu1gnobxb.css';
import '../../css/r/r_8asobqy.css';
import '../../css/f/fwij3dbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wu1gnobxb"/><path class="r_8asobqy"/><path class="fwij3dbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-island-48-bold" {...props}></Icon>
