<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjsrzsb4b.css';
import '../../css/v/vt4p30p5y.css';
import '../../css/n/n3xkk3bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cjsrzsb4b"/><path class="vt4p30p5y"/><path class="n3xkk3bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:liquid-hydrogen-48" {...props}></Icon>
