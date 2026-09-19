<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es35w10kr.css';
import '../../css/j/jzeym_btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es35w10kr"/><path class="jzeym_btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:guitar-amp-filled" {...props}></Icon>
