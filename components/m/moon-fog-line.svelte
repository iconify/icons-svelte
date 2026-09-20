<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh9mg9beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh9mg9beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-fog-line" {...props}></Icon>
