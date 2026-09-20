<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsepixbkn.css';
import '../../css/c/cgtb-8b0p.css';
import '../../css/d/djamc0beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsepixbkn"/><path class="cgtb-8b0p"/><path class="djamc0beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cusdc" {...props}></Icon>
