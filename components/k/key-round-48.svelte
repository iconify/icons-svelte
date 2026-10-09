<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8q6kzbna.css';
import '../../css/a/a25ffhnff.css';
import '../../css/o/o3vxjxbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8q6kzbna"/><path class="a25ffhnff"/><path class="o3vxjxbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:key-round-48" {...props}></Icon>
