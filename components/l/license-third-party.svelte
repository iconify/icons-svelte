<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiwjo4boz.css';
import '../../css/d/dt0zo1djr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kiwjo4boz"/><path class="dt0zo1djr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:license-third-party" {...props}></Icon>
