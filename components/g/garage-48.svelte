<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw7-9fnfj.css';
import '../../css/f/fu7nvvbdq.css';
import '../../css/n/n-t7_zj3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hw7-9fnfj"/><path class="fu7nvvbdq"/><path class="n-t7_zj3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:garage-48" {...props}></Icon>
