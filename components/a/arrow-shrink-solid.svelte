<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e25psnbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e25psnbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-shrink-solid" {...props}></Icon>
