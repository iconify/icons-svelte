<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llnax_bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="llnax_bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:alien-solid" {...props}></Icon>
