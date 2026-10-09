<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-pj1ullj.css';
import '../../css/v/vfwj5rb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l-pj1ullj"/><path class="vfwj5rb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calculator-48-bold" {...props}></Icon>
