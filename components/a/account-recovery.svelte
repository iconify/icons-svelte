<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/umi_lsbuk.css';
import '../../css/r/r93eu13-n.css';
import '../../css/r/ryl82g88k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umi_lsbuk"/><path class="r93eu13-n"/><path class="ryl82g88k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:account-recovery" {...props}></Icon>
