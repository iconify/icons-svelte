<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6t5c-oxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="o6t5c-oxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:arrow-up" {...props}></Icon>
