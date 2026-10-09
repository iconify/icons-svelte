<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3b3aw3dq.css';
import '../../css/v/v7n04acgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j3b3aw3dq"/><path class="v7n04acgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:audit-48" {...props}></Icon>
