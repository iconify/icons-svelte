<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4g_2xbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4g_2xbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-check" {...props}></Icon>
