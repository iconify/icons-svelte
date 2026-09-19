<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/ct9lq-phd.css';
import '../../css/n/npzbi206w.css';
import '../../css/l/lqkmkym5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ct9lq-phd"/><circle class="npzbi206w"/><path class="lqkmkym5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chess-bishop" {...props}></Icon>
