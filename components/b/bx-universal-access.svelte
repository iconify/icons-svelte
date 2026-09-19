<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkgfbqhls.css';
import '../../css/w/wckr9kb1z.css';
import '../../css/q/q285h9bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="zkgfbqhls"/><path class="wckr9kb1z"/><path class="q285h9bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-universal-access" {...props}></Icon>
