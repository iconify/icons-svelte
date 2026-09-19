<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtvndxeyx.css';
import '../../css/n/n8ie0gbut.css';
import '../../css/y/yxx4r0hjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtvndxeyx"/><path class="n8ie0gbut"/><path clip-rule="evenodd" class="yxx4r0hjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:power-button-outline" {...props}></Icon>
