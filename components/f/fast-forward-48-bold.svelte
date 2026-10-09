<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8odd-vsc.css';
import '../../css/o/orpof4bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h8odd-vsc"/><path class="orpof4bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fast-forward-48-bold" {...props}></Icon>
