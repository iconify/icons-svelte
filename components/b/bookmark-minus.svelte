<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsyyo2b3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsyyo2b3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bookmark-minus" {...props}></Icon>
