<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mime5u9mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mime5u9mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:man-arm-raises-2-alternate-remix" {...props}></Icon>
