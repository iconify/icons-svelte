<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e77v1eb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e77v1eb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:low-bars2x-outline" {...props}></Icon>
