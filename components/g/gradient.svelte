<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjqd8pbho.css';
import '../../css/t/tgp27vi-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zjqd8pbho"/><path class="tgp27vi-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gradient" {...props}></Icon>
