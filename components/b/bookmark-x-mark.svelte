<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6dqxlbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6dqxlbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bookmark-x-mark" {...props}></Icon>
