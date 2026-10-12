<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byv5v7eqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="byv5v7eqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pyramid-filled" {...props}></Icon>
