<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac9x35hjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ac9x35hjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:axis-rotation" {...props}></Icon>
