<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_07ktnny.css';
import '../../css/j/jf0u8bbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_07ktnny"/><path class="jf0u8bbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-stream-bold-duotone" {...props}></Icon>
