<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-70ol5nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l-70ol5nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:entertainment-control-button-power-1-power-button-on-off" {...props}></Icon>
