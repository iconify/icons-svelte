<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czw5mnb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czw5mnb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-check" {...props}></Icon>
