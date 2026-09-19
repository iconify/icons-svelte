<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj3y0cblt.css';
import '../../css/v/v2096mbgt.css';
import '../../css/g/gr_mehv_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xj3y0cblt"/><path class="v2096mbgt"/><path class="gr_mehv_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-shuffle-strong" {...props}></Icon>
