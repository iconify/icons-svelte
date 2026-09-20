<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgt_puboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vgt_puboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mouse-remix" {...props}></Icon>
