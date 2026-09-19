<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegyyab8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oegyyab8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rewind-four-x" {...props}></Icon>
