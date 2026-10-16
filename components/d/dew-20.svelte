<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4x8k8clu.css';
import '../../css/k/kiv3_z61q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k4x8k8clu"/><path class="kiv3_z61q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dew-20" {...props}></Icon>
