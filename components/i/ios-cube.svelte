<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxzshjbvd.css';
import '../../css/p/pd4mgccgx.css';
import '../../css/o/oqp24fb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lxzshjbvd"/><path class="pd4mgccgx"/><path class="oqp24fb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cube" {...props}></Icon>
