<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv0tefs3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv0tefs3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-2-flame" {...props}></Icon>
