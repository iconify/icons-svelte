<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjkhnvb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjkhnvb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:michelin-star-filled" {...props}></Icon>
