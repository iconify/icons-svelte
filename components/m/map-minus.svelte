<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcso0lb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcso0lb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:map-minus" {...props}></Icon>
