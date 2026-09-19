<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwvlvdbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwvlvdbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-running" {...props}></Icon>
