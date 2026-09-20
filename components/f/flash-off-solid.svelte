<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snby8fxbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="snby8fxbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flash-off-solid" {...props}></Icon>
