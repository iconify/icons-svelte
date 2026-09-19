<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0gu_qbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0gu_qbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:abstract" {...props}></Icon>
