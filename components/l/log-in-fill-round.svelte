<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5k00k32a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5k00k32a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:log-in-fill-round" {...props}></Icon>
