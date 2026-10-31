<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg1h1q77m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg1h1q77m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:command-bulk-round" {...props}></Icon>
