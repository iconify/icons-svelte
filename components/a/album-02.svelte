<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/q3wi6uwqm.css';
import '../../css/f/fvd7ocb9d.css';
import '../../css/s/sn7cxmbyk.css';
import '../../css/v/v0trjrv3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wi6uwqm"/><path class="fvd7ocb9d"/><path class="sn7cxmbyk"/><path class="v0trjrv3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:album-02" {...props}></Icon>
