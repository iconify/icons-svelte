<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb3l59rwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nb3l59rwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kayak-paddle-crossing-kayak" {...props}></Icon>
