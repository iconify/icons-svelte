<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymlwebwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iymlwebwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:carrot-solid" {...props}></Icon>
