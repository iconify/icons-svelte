<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp1g86hto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp1g86hto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-down-filled" {...props}></Icon>
