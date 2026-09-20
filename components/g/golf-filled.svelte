<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i7n49ic5b.css';
import '../../css/e/e20wemfyj.css';
import '../../css/f/fa1egib0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i7n49ic5b"/><path class="e20wemfyj"/><path class="fa1egib0t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:golf-filled" {...props}></Icon>
