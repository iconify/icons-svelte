<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2mhu05yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2mhu05yt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-cny-line" {...props}></Icon>
