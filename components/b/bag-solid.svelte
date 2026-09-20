<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc5a79bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xc5a79bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bag-solid" {...props}></Icon>
