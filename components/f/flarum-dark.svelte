<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqnt8yb-o.css';
import '../../css/x/xvo7kubqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqnt8yb-o"/><path class="xvo7kubqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flarum-dark" {...props}></Icon>
