<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a6b1sjbce.css';
import '../../css/j/jai1xcbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a6b1sjbce"/><path clip-rule="evenodd" class="jai1xcbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:padlock-square-2-flat" {...props}></Icon>
