<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir-l3d4bi.css';
import '../../css/o/od-orcbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir-l3d4bi"/><path class="od-orcbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:deepmind" {...props}></Icon>
