<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsahk5bgt.css';
import '../../css/d/d1j7k6bho.css';
import '../../css/h/hae377b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qsahk5bgt"/><path class="d1j7k6bho"/><path class="hae377b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hourglass-48-bold" {...props}></Icon>
