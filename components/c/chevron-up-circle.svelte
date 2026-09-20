<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l27dxibsi.css';
import '../../css/m/mpgu6g9gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="l27dxibsi"/><path clip-rule="evenodd" class="mpgu6g9gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chevron-up-circle" {...props}></Icon>
