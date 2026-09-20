<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t19w5m.css';
import '../../css/t/t5pxry.css';
import '../../css/w/wbymzg.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-82.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGcSVXwbeB"><path class="t19w5m t5pxry"/><path class="t5pxry wbymzg"/></mask></defs><path mask="url(#SVGcSVXwbeB)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:mastodon-filled" {...props}></Icon>
