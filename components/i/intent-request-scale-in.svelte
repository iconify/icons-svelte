<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gffi6mjqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gffi6mjqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:intent-request-scale-in" {...props}></Icon>
