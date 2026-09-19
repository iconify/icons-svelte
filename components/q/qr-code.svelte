<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mimhvz02b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mimhvz02b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:qr-code" {...props}></Icon>
