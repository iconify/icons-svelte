<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usxmd2bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usxmd2bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kucoin" {...props}></Icon>
