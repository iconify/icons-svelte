<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/einr-yb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="einr-yb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lasso-tool-remix" {...props}></Icon>
