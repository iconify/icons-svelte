<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw0pvw1ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="dw0pvw1ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:radioactive" {...props}></Icon>
