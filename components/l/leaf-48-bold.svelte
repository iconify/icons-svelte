<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3hcjybun.css';
import '../../css/s/sq0k58bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r3hcjybun"/><path class="sq0k58bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:leaf-48-bold" {...props}></Icon>
