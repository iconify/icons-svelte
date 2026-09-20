<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr3l9zb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr3l9zb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-off-line" {...props}></Icon>
