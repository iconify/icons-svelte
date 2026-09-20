<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q80p7-jst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q80p7-jst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:customer-support-1-remix" {...props}></Icon>
