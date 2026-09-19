<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd5t47bei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bd5t47bei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:connection-signal-alt" {...props}></Icon>
