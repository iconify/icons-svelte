<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-lm-kbpu.css';
import '../../css/k/k4cp8nxvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h-lm-kbpu"/><path class="k4cp8nxvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:machine-learning" {...props}></Icon>
