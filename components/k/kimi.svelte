<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9j31zbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y9j31zbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:kimi" {...props}></Icon>
