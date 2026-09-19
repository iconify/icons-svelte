<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swwrsubca.css';
import '../../css/g/g0ga_t5io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="swwrsubca"/><path class="g0ga_t5io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:camera" {...props}></Icon>
