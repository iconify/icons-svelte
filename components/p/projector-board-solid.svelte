<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkb-87aiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fkb-87aiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:projector-board-solid" {...props}></Icon>
