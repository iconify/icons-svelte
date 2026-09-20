<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpus6cb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpus6cb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:progress-3-line" {...props}></Icon>
