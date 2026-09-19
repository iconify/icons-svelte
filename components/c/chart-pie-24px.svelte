<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_amit_yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_amit_yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-pie-24px" {...props}></Icon>
