<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imhg5cbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="imhg5cbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-transfusion2x-outline" {...props}></Icon>
