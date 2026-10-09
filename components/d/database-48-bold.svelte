<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ioum2-g.css';
import '../../css/b/bwjcn-b3e.css';
import '../../css/k/k-kjrmbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2ioum2-g"/><path class="bwjcn-b3e"/><path class="k-kjrmbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:database-48-bold" {...props}></Icon>
