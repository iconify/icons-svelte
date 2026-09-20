<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq5gilrjk.css';
import '../../css/c/ck3-yx4dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq5gilrjk"/><path class="ck3-yx4dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-instrument-ambulance-bed-bold" {...props}></Icon>
