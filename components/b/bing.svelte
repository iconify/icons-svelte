<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2i50-arv.css';
import '../../css/a/adhi_y29i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2i50-arv"/><path class="adhi_y29i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:bing" {...props}></Icon>
