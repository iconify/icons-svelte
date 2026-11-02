<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unigbil3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unigbil3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-lock-fill" {...props}></Icon>
