<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le7jai.css';
import '../../css/j/judi8a.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGBTh34dFN"><path class="le7jai"/><path class="judi8a"/></mask></defs><path mask="url(#SVGBTh34dFN)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:pixelfed-filled" {...props}></Icon>
