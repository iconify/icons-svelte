<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sikxymb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sikxymb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bone-gloss" {...props}></Icon>
