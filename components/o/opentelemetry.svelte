<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5is1to6c.css';
import '../../css/u/ud1-bgmma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5is1to6c"/><path class="ud1-bgmma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opentelemetry" {...props}></Icon>
