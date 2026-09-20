<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9kv82bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y9kv82bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:meta-solid" {...props}></Icon>
