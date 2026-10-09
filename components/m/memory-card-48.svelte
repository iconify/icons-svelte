<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi5qdgtra.css';
import '../../css/o/owfc160qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oi5qdgtra"/><path class="owfc160qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:memory-card-48" {...props}></Icon>
