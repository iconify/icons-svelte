<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aitkfzbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="aitkfzbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:high-bars2x-outline" {...props}></Icon>
