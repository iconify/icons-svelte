<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s25dc911s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s25dc911s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:right-to-left" {...props}></Icon>
