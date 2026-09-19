<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y84bdgn_e.css';
import '../../css/d/dw5u3v8yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y84bdgn_e"/><path class="dw5u3v8yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:haze-night" {...props}></Icon>
