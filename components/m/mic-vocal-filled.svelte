<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl8fmdb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl8fmdb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mic-vocal-filled" {...props}></Icon>
