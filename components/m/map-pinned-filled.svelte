<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xnjzbga.css';
import '../../css/g/gcamo9w-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6xnjzbga"/><path clip-rule="evenodd" class="gcamo9w-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pinned-filled" {...props}></Icon>
