<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nym2i-c8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nym2i-c8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-parentheses" {...props}></Icon>
