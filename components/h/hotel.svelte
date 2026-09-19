<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0_uobbtg.css';
import '../../css/u/ussqqxbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="r0_uobbtg"/><path class="ussqqxbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:hotel" {...props}></Icon>
