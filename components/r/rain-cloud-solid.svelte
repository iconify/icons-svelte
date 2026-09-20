<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz00btnxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gz00btnxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:rain-cloud-solid" {...props}></Icon>
