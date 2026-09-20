<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i91ajtrke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i91ajtrke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:copyright-off-solid" {...props}></Icon>
