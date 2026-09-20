<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5xdmn.css';
import '../../css/c/clv-by.css';
import '../../css/o/oxx-om.css';
import '../../css/q/qnwgpe.css';
import '../../css/b/botfzx.css';
import '../../css/g/gd_4-q.css';
import '../../css/s/so-from-62.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG9CrvrcDy"><path class="c5xdmn clv-by"/><path class="c5xdmn oxx-om qnwgpe"/></mask></defs><path mask="url(#SVG9CrvrcDy)" class="botfzx"/><path class="c5xdmn gd_4-q qnwgpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-off" {...props}></Icon>
