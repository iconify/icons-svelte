<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjpct4_2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjpct4_2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-2-round" {...props}></Icon>
