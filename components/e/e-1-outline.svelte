<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs_8zwu2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vs_8zwu2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:e-1-outline" {...props}></Icon>
