<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/apst68bcm.css';
import '../../css/v/v5dr9sbpb.css';
import '../../css/l/l0am3zboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apst68bcm"/><path class="v5dr9sbpb"/><path class="l0am3zboh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:charging-operator" {...props}></Icon>
