<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/javag0hlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="javag0hlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-upload-01" {...props}></Icon>
