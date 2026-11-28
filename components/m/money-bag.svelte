<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l62y4hg5y.css';
import '../../css/z/zyotwulsl.css';
import '../../css/f/fb-49ybaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l62y4hg5y"/><path class="zyotwulsl"/><path class="fb-49ybaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:money-bag" {...props}></Icon>
