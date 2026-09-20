<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6r7xl_qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6r7xl_qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-handsdown" {...props}></Icon>
