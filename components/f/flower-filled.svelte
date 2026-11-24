<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjs88jsib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yjs88jsib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flower-filled" {...props}></Icon>
