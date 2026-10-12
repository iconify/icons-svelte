<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vszamwk3o.css';
import '../../css/t/twy8dkvem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vszamwk3o"/><path clip-rule="evenodd" class="twy8dkvem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hd-filled" {...props}></Icon>
