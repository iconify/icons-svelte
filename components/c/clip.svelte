<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt8hpebez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lt8hpebez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:clip" {...props}></Icon>
