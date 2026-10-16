<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0rnyhxzu.css';
import '../../css/y/yv3ldgslo.css';
import '../../css/v/vd38aibtw.css';
import '../../css/q/qr5-gge8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j0rnyhxzu"/><path class="yv3ldgslo"/><path class="vd38aibtw"/><path class="qr5-gge8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-cell-20" {...props}></Icon>
