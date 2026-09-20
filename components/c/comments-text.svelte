<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0mv5_-ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0mv5_-ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comments-text" {...props}></Icon>
