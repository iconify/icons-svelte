<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihcg3e6qc.css';
import '../../css/n/nnq4tpzbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ihcg3e6qc"/><path class="nnq4tpzbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rain-gauge-20" {...props}></Icon>
