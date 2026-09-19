<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke1y0kp2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ke1y0kp2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chaplaincy" {...props}></Icon>
