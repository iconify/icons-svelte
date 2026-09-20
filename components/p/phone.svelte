<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmad1v5mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rmad1v5mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone" {...props}></Icon>
