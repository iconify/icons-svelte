<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6fjbw84x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6fjbw84x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:location-3-fill" {...props}></Icon>
