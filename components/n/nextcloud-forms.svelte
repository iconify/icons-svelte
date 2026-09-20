<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp1v2sdoj.css';
import '../../css/r/rth9se2ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qp1v2sdoj"/><path class="rth9se2ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-forms" {...props}></Icon>
