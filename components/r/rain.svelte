<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyfuw7bce.css';
import '../../css/i/iu0eltnal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xyfuw7bce"/><path class="iu0eltnal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:rain" {...props}></Icon>
