<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f603m2bbo.css';
import '../../css/i/iqekx2b4d.css';
import '../../css/t/t433albvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f603m2bbo"/><path class="iqekx2b4d"/><path class="t433albvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:artificial-intelligence-07" {...props}></Icon>
