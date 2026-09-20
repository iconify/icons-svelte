<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9kuzwb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9kuzwb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-h" {...props}></Icon>
