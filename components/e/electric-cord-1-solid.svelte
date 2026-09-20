<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p25m-zfzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p25m-zfzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:electric-cord-1-solid" {...props}></Icon>
