<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsw1i4ejt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsw1i4ejt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-line" {...props}></Icon>
