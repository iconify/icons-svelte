<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag2418r2o.css';
import '../../css/x/xw-233z3g.css';
import '../../css/l/len3wybrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ag2418r2o"/><path class="xw-233z3g"/><path class="len3wybrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:receipt-outline" {...props}></Icon>
