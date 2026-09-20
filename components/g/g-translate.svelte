<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qchr4-bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qchr4-bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:g-translate" {...props}></Icon>
