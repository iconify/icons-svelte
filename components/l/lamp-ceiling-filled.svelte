<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txccpm--h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txccpm--h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-ceiling-filled" {...props}></Icon>
