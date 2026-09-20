<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0225_9gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0225_9gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-ruby" {...props}></Icon>
