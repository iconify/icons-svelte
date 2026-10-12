<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy3btfbfu.css';
import '../../css/b/b79ewjo9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fy3btfbfu"/><path class="b79ewjo9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brain-48-bold" {...props}></Icon>
