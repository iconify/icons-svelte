<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw76jf7vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw76jf7vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:deezer-logo" {...props}></Icon>
