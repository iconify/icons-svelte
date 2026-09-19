<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2tprwbpc.css';
import '../../css/v/vwxhrfbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="x2tprwbpc"/><path class="vwxhrfbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flower-sharp" {...props}></Icon>
