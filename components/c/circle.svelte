<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9o2i1oac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="x9o2i1oac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:circle" {...props}></Icon>
