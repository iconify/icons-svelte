<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mimxhhbzg.css';
import '../../css/l/l12r2ccpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mimxhhbzg"/><path class="l12r2ccpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:copy-solid" {...props}></Icon>
