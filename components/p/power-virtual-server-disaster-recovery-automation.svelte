<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5---93ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v5---93ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:power-virtual-server-disaster-recovery-automation" {...props}></Icon>
