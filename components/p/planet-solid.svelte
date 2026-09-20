<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7grsg8zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7grsg8zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:planet-solid" {...props}></Icon>
