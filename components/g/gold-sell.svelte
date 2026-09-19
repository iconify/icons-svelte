<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a16vnybjj.css';
import '../../css/g/gp0egaclj.css';
import '../../css/x/xxdfd3c6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a16vnybjj"/><circle class="gp0egaclj"/><path class="xxdfd3c6y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gold-sell" {...props}></Icon>
