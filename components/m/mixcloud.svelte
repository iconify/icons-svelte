<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szppspbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1408};
const content = `<path class="szppspbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mixcloud" {...props}></Icon>
