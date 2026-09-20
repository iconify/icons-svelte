<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz36zmk8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz36zmk8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:playlist" {...props}></Icon>
