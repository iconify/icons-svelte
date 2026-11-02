<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4j21obxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4j21obxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-2-off-line" {...props}></Icon>
