<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5edrzb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5edrzb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bookmark-off-filled" {...props}></Icon>
