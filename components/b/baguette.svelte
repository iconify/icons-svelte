<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsm0-megr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsm0-megr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:baguette" {...props}></Icon>
