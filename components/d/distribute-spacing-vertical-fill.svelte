<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxsc2h-na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxsc2h-na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-vertical-fill" {...props}></Icon>
