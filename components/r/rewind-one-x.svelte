<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc7v3q69r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dc7v3q69r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rewind-one-x" {...props}></Icon>
