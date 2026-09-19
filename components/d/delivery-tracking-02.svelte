<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g-5fe2a3l.css';
import '../../css/l/lgszabjvu.css';
import '../../css/e/e1h8zkb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-5fe2a3l"/><path class="lgszabjvu"/><path class="e1h8zkb4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:delivery-tracking-02" {...props}></Icon>
