<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2qsx7eke.css';
import '../../css/e/e32k5njcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="e2qsx7eke"/><path class="e32k5njcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:old-navy" {...props}></Icon>
