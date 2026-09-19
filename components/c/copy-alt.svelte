<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfnld8b9e.css';
import '../../css/h/hum_vbh1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfnld8b9e"/><path class="hum_vbh1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:copy-alt" {...props}></Icon>
