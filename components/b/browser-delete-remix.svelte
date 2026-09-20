<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei_60e-bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ei_60e-bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-delete-remix" {...props}></Icon>
