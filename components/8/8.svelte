<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx293rnkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vx293rnkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:8" {...props}></Icon>
