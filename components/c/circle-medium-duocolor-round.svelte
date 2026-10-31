<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0g0lp3_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0g0lp3_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-medium-duocolor-round" {...props}></Icon>
