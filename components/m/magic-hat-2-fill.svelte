<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvwdr9byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvwdr9byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-hat-2-fill" {...props}></Icon>
