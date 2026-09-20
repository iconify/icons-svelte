<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcuou08cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcuou08cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-lock-outline" {...props}></Icon>
