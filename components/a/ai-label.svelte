<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy8f-purm.css';
import '../../css/v/v__h0hbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dy8f-purm"/><path class="v__h0hbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-label" {...props}></Icon>
