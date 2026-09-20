<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg6jq9bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6jq9bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fries-line" {...props}></Icon>
