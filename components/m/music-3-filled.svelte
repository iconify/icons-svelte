<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c67r7smis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c67r7smis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:music-3-filled" {...props}></Icon>
