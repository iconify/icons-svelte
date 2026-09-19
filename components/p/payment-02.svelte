<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/x/xgfrcogqu.css';
import '../../css/j/jixhl9msz.css';
import '../../css/n/nh05mtbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgfrcogqu"/><path class="jixhl9msz"/><path class="nh05mtbfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:payment-02" {...props}></Icon>
