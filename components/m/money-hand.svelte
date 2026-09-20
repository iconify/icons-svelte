<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgckyq4_m.css';
import '../../css/s/sy9lcgb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qgckyq4_m"/><path class="sy9lcgb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:money-hand" {...props}></Icon>
