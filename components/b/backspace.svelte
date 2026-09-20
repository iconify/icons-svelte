<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrtgfjb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrtgfjb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:backspace" {...props}></Icon>
