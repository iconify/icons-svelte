<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4xkvhbmt.css';
import '../../css/l/l09236icr.css';
import '../../css/q/qfnn6de1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4xkvhbmt"/><circle class="l09236icr"/><path class="qfnn6de1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flashlight-outline" {...props}></Icon>
