<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpoubbo_e.css';
import '../../css/u/uogpnc8_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="uogpnc8_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-4" {...props}></Icon>
