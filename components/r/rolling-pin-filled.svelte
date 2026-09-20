<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe58r_k9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe58r_k9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rolling-pin-filled" {...props}></Icon>
