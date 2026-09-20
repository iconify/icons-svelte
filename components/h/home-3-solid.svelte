<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwap7wbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nwap7wbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:home-3-solid" {...props}></Icon>
