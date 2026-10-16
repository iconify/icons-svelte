<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qntmgtbht.css';
import '../../css/m/mfqrv5y5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qntmgtbht"/><path class="mfqrv5y5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:and-gate-20-bold" {...props}></Icon>
