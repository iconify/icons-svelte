<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4-1nacqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4-1nacqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bookmark-x-filled" {...props}></Icon>
