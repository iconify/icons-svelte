<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juilb0dgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="juilb0dgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:qiskit" {...props}></Icon>
