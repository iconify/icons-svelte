<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an4eqo_8f.css';
import '../../css/l/lr_186u5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="an4eqo_8f"/><path clip-rule="evenodd" class="lr_186u5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:investment-selection-solid" {...props}></Icon>
