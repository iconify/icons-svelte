<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-l6sbc0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-l6sbc0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-x-filled" {...props}></Icon>
