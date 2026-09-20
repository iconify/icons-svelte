<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etwsosu7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="etwsosu7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hooli" {...props}></Icon>
