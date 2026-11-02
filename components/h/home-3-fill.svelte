<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5ljbpb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5ljbpb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-3-fill" {...props}></Icon>
