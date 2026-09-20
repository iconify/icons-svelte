<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbuwyijec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tbuwyijec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:departure-time" {...props}></Icon>
