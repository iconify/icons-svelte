<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/drttxikxo.css';
import '../../css/c/cr3ta5bbg.css';
import '../../css/p/p9-zrkb4g.css';
import '../../css/g/guewfbcxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drttxikxo"/><path class="cr3ta5bbg"/><path class="p9-zrkb4g"/><path class="guewfbcxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ios-settings" {...props}></Icon>
