<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xuy7impgh.css';
import '../../css/w/wgu_5sbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xuy7impgh"/><path clip-rule="evenodd" class="wgu_5sbxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:no-word-wrap-flat" {...props}></Icon>
