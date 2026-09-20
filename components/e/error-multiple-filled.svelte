<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/codtw1b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="codtw1b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:error-multiple-filled" {...props}></Icon>
