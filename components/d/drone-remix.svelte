<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xila1ke2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xila1ke2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:drone-remix" {...props}></Icon>
