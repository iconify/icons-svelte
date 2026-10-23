<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuln7pb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uuln7pb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:quantum-qpu" {...props}></Icon>
