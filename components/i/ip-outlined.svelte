<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv_l6fzvt.css';
import '../../css/r/rz8l7i1vb.css';
import '../../css/q/qixglcefr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv_l6fzvt"/><path class="rz8l7i1vb"/><path class="qixglcefr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:ip-outlined" {...props}></Icon>
