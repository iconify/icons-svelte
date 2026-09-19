<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtg72i0ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtg72i0ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-2-filled" {...props}></Icon>
