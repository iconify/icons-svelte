<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atb_wxrsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="atb_wxrsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:projector-board-solid" {...props}></Icon>
