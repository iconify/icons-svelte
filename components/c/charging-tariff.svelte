<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/baf6r5xsc.css';
import '../../css/f/fpneqjbpl.css';
import '../../css/k/k7qnch2qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="baf6r5xsc"/><circle class="fpneqjbpl"/><path class="k7qnch2qn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:charging-tariff" {...props}></Icon>
