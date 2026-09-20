<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t949v_b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t949v_b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-fill" {...props}></Icon>
