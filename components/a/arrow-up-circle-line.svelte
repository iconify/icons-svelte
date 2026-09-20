<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmq08gb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmq08gb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-up-circle-line" {...props}></Icon>
