<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm3uvob8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm3uvob8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-edge" {...props}></Icon>
