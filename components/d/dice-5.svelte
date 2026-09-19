<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoubbo_e.css';
import '../../css/f/fiqo5rbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="fiqo5rbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-5" {...props}></Icon>
