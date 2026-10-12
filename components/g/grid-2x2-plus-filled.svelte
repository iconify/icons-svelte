<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6pox3bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6pox3bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:grid-2x2-plus-filled" {...props}></Icon>
