<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvh5j5b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xvh5j5b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:respirator" {...props}></Icon>
