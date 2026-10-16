<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtu0zrbrj.css';
import '../../css/o/o1kbcc50r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rtu0zrbrj"/><path class="o1kbcc50r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crimper-48" {...props}></Icon>
