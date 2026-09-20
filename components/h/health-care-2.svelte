<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnjb_7x4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qnjb_7x4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:health-care-2" {...props}></Icon>
