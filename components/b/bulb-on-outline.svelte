<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lusdtq8gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lusdtq8gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-on-outline" {...props}></Icon>
