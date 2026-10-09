<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc6qzlmiu.css';
import '../../css/k/kpa1g8jdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qc6qzlmiu"/><path class="kpa1g8jdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pliers-48" {...props}></Icon>
