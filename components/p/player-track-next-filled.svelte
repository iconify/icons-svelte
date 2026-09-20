<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkqw8efuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkqw8efuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-track-next-filled" {...props}></Icon>
