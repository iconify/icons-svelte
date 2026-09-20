<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue03v71pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ue03v71pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:expand-horizontal-1" {...props}></Icon>
