<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld2931_iv.css';
import '../../css/s/s9ab3vb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ld2931_iv"/><path class="s9ab3vb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-info" {...props}></Icon>
