<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m--fc-7uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m--fc-7uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-markdown" {...props}></Icon>
