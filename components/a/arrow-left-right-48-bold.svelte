<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfmifebfq.css';
import '../../css/c/c4iz7xb8s.css';
import '../../css/q/qdy37eb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rfmifebfq"/><path class="c4iz7xb8s"/><path class="qdy37eb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-right-48-bold" {...props}></Icon>
