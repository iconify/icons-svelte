<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhsv77bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bhsv77bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:galactic-republic" {...props}></Icon>
