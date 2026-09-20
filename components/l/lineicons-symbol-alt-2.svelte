<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssww8xbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ssww8xbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:lineicons-symbol-alt-2" {...props}></Icon>
