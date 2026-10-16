<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrq7csbic.css';
import '../../css/k/kbvc24bmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nrq7csbic"/><path class="kbvc24bmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-sink-20-bold" {...props}></Icon>
