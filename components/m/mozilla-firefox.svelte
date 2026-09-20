<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu5lc3b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu5lc3b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mozilla-firefox" {...props}></Icon>
