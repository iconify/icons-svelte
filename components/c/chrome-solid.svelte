<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdf8vni2w.css';
import '../../css/k/ka0y_qb6x.css';
import '../../css/g/g6llgnykv.css';
import '../../css/i/ib6autsjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qdf8vni2w"/><path class="ka0y_qb6x"/><path class="g6llgnykv"/><path class="ib6autsjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:chrome-solid" {...props}></Icon>
