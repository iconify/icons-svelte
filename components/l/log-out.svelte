<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkzeu-g_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkzeu-g_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:log-out" {...props}></Icon>
