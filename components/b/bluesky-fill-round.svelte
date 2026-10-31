<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4kzwdb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4kzwdb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bluesky-fill-round" {...props}></Icon>
