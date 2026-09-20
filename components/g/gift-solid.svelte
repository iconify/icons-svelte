<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0xf62b4y.css';
import '../../css/e/e5i6xxbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e0xf62b4y"/><path class="e5i6xxbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:gift-solid" {...props}></Icon>
