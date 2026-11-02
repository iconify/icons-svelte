<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waicl-j-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waicl-j-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:filter-fill" {...props}></Icon>
