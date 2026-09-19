<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3zb4bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vl3zb4bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:question-mark2x-outline" {...props}></Icon>
