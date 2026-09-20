<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7o2f7z5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7o2f7z5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:move-to-bottom-bold" {...props}></Icon>
