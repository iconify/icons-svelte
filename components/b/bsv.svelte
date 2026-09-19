<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl_0t8b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gl_0t8b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bsv" {...props}></Icon>
