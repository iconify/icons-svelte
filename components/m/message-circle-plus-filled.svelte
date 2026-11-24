<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9mpb68_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l9mpb68_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-plus-filled" {...props}></Icon>
