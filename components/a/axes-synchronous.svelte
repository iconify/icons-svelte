<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5o5d4ter.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y5o5d4ter"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:axes-synchronous" {...props}></Icon>
