<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvlzrldrv.css';
import '../../css/b/b8lwwppwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvlzrldrv"/><path class="b8lwwppwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:headset" {...props}></Icon>
