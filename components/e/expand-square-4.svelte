<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3d8sv4oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="k3d8sv4oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:expand-square-4" {...props}></Icon>
