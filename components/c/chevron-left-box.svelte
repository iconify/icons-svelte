<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbcc51ung.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbcc51ung"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-left-box" {...props}></Icon>
