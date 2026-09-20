<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5xdmn.css';
import '../../css/z/z1wsyp.css';
import '../../css/o/oxx-om.css';
import '../../css/t/t-ne3j.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-62.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGoi2mdcdx"><path class="c5xdmn z1wsyp"/><path class="c5xdmn oxx-om t-ne3j"/></mask></defs><path mask="url(#SVGoi2mdcdx)" class="botfzx"/><path class="c5xdmn gd_4-q t-ne3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:moon-simple-off" {...props}></Icon>
