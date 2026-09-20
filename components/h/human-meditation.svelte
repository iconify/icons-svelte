<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gibvwl8bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gibvwl8bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-meditation" {...props}></Icon>
