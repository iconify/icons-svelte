<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce_m_3btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ce_m_3btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:paper" {...props}></Icon>
