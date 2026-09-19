<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qchdvmbcp.css';
import '../../css/c/cwo24bbfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="qchdvmbcp"/><path class="cwo24bbfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:media-changer-line" {...props}></Icon>
