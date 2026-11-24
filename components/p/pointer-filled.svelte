<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tilvpubxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tilvpubxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pointer-filled" {...props}></Icon>
