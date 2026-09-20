<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmd42x_uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="cmd42x_uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:lock-key-filled" {...props}></Icon>
