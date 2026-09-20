<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld4osb5km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ld4osb5km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:inline-skating" {...props}></Icon>
