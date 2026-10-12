<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx7l5abtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dx7l5abtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-open-text-filled" {...props}></Icon>
