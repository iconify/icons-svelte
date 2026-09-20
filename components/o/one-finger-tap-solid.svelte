<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkyaeo7fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jkyaeo7fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:one-finger-tap-solid" {...props}></Icon>
