<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o179kmblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o179kmblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nvidia-light" {...props}></Icon>
