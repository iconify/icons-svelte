<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4gawx0pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4gawx0pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kettle-pour-over" {...props}></Icon>
