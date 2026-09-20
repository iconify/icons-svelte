<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb3qrybmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb3qrybmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:diamond-filled" {...props}></Icon>
