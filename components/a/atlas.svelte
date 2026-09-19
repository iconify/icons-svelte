<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsfs2btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ecsfs2btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:atlas" {...props}></Icon>
