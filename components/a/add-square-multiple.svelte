<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/vmchpqbpy.css';
import '../../css/i/ideagcboz.css';
import '../../css/e/e5x2664gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vmchpqbpy"/><rect class="ideagcboz"/><path class="e5x2664gk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:add-square-multiple" {...props}></Icon>
