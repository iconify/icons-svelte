<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gutzyv.css';
import '../../css/t/t5pxry.css';
import '../../css/o/oxx-om.css';
import '../../css/x/x1bqbh.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGvFptu4QO"><path class="gutzyv t5pxry"/><path class="oxx-om t5pxry x1bqbh"/></mask></defs><path mask="url(#SVGvFptu4QO)" class="botfzx"/><path class="gd_4-q t5pxry x1bqbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:cloud-alt-off-filled" {...props}></Icon>
