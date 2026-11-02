<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfquvubot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfquvubot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:down-small-line" {...props}></Icon>
