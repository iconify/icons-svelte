<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en8iypeyz.css';
import '../../css/q/qgciedcam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="en8iypeyz"/><path clip-rule="evenodd" class="qgciedcam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:lock-circle-solid" {...props}></Icon>
