<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liisccame.css';
import '../../css/h/h6e7wy_ms.css';
import '../../css/a/a24rft0do.css';
import '../../css/n/nnwy57bcc.css';
import '../../css/y/yqhmzccbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="liisccame"/><path class="h6e7wy_ms"/><path class="a24rft0do"/><path class="nnwy57bcc"/><path class="yqhmzccbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-fleet-48-bold" {...props}></Icon>
