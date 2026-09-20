<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shfib-biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shfib-biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-tag-outline" {...props}></Icon>
