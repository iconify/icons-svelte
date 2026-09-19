<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg8sq1b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg8sq1b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rain" {...props}></Icon>
