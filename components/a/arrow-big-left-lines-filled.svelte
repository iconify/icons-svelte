<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtrq_0lkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtrq_0lkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-left-lines-filled" {...props}></Icon>
