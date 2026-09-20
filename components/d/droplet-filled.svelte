<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zba_mr_xo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zba_mr_xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:droplet-filled" {...props}></Icon>
