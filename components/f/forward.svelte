<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7avmm_pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s7avmm_pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:forward" {...props}></Icon>
