<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-p09f.css';
import '../../css/t/t5pxry.css';
import '../../css/u/u7rb2p.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-66.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGuzRaresM"><path class="i-p09f t5pxry"/><path class="t5pxry u7rb2p"/></mask></defs><path mask="url(#SVGuzRaresM)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:confirm-square-filled" {...props}></Icon>
