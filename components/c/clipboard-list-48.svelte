<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxzfl5btn.css';
import '../../css/w/wsygfsbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lxzfl5btn"/><path class="wsygfsbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-list-48" {...props}></Icon>
