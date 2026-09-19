<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0dq7ub6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x0dq7ub6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:n2x-outline" {...props}></Icon>
