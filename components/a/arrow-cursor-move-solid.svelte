<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4pejze1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j4pejze1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-move-solid" {...props}></Icon>
