<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilfpzycyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilfpzycyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-horizontal-round" {...props}></Icon>
