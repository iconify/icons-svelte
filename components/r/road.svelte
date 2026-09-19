<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz-l9cc9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1856,"height":1280};
const content = `<path class="oz-l9cc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:road" {...props}></Icon>
