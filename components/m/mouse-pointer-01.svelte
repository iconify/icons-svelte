<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmxstrbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmxstrbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-pointer-01" {...props}></Icon>
