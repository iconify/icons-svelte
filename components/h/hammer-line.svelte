<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo6cfv3dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo6cfv3dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hammer-line" {...props}></Icon>
