<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csm4l4bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csm4l4bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:archive-filled" {...props}></Icon>
