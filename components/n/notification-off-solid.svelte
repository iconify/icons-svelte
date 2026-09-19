<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se48-pe8k.css';
import '../../css/r/repczfbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se48-pe8k"/><path clip-rule="evenodd" class="repczfbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-off-solid" {...props}></Icon>
