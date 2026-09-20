<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyaf8byaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyaf8byaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-arrow-up-down-outline" {...props}></Icon>
