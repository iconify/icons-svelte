<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpl049buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpl049buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:columns-3-filled" {...props}></Icon>
