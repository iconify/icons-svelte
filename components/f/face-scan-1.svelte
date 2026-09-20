<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scyo_vb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="scyo_vb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:face-scan-1" {...props}></Icon>
