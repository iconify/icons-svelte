<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvhu8yb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvhu8yb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ads-off" {...props}></Icon>
