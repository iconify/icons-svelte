<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9synkbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u9synkbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fork-knife-solid" {...props}></Icon>
