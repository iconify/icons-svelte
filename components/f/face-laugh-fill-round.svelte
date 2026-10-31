<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw0842bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw0842bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-laugh-fill-round" {...props}></Icon>
