<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/phpuyfbcc.css';
import '../../css/g/gqvtjotgp.css';
import '../../css/n/nje5g0bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="phpuyfbcc"/><path class="gqvtjotgp"/><path class="nje5g0bbx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:multiple-pages-delete" {...props}></Icon>
