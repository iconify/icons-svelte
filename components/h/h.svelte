<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xspq7il3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xspq7il3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:h" {...props}></Icon>
