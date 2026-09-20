<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp7d-bcfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vp7d-bcfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:politics-speech-solid" {...props}></Icon>
