<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv9z5ggml.css';
import '../../css/o/o8wjvtbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fv9z5ggml"/><path class="o8wjvtbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-pass-dark" {...props}></Icon>
