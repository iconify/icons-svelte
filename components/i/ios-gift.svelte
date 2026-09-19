<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omu-7_bkt.css';
import '../../css/y/yi7yklpos.css';
import '../../css/l/li6tqsbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omu-7_bkt"/><path class="yi7yklpos"/><path class="li6tqsbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-gift" {...props}></Icon>
