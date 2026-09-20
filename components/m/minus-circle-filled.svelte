<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyx2zp.css';
import '../../css/t/t5pxry.css';
import '../../css/i/i4emph.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGwJ9Rwipn"><path class="pyx2zp t5pxry"/><path class="i4emph t5pxry"/></mask></defs><path mask="url(#SVGwJ9Rwipn)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:minus-circle-filled" {...props}></Icon>
