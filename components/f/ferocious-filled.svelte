<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iau3g_b6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iau3g_b6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ferocious-filled" {...props}></Icon>
