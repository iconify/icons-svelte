<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyaq9f7-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qyaq9f7-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:globe-outline" {...props}></Icon>
