<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhy-5k__b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhy-5k__b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-close-bookmark-1-bold" {...props}></Icon>
