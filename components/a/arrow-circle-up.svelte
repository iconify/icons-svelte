<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvu5-paxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="tvu5-paxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-circle-up" {...props}></Icon>
