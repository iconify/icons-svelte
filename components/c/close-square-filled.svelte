<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-p09f.css';
import '../../css/t/t5pxry.css';
import '../../css/m/m5kcdn.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGl6h8Sb7u"><path class="i-p09f t5pxry"/><path class="m5kcdn t5pxry"/></mask></defs><path mask="url(#SVGl6h8Sb7u)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:close-square-filled" {...props}></Icon>
