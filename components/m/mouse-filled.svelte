<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slgm1gbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="slgm1gbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-filled" {...props}></Icon>
