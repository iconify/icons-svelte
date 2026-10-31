<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyvgjdbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyvgjdbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bubble-fill-round" {...props}></Icon>
