<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ioum2-g.css';
import '../../css/k/k7bxcbctl.css';
import '../../css/z/z34g1fbbc.css';
import '../../css/l/l9jgh7bvz.css';
import '../../css/s/st45emjbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2ioum2-g"/><path class="k7bxcbctl"/><path class="z34g1fbbc"/><path class="l9jgh7bvz"/><path class="st45emjbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:database-plus-48-bold" {...props}></Icon>
