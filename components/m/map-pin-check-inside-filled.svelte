<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bga350_7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bga350_7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-check-inside-filled" {...props}></Icon>
