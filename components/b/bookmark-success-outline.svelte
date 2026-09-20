<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s--_y-b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s--_y-b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-success-outline" {...props}></Icon>
