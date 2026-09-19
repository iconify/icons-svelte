<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drvi-fbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drvi-fbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:code-sharp" {...props}></Icon>
