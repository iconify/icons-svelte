<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9czz4bal.css';
import '../../css/x/xl9bybcex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="xl9bybcex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-bolt-48" {...props}></Icon>
