<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8nyf9k4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8nyf9k4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:baseball-round" {...props}></Icon>
