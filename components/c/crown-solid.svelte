<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1-9e5ove.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1-9e5ove"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:crown-solid" {...props}></Icon>
