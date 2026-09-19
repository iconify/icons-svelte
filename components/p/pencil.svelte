<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asdlnrbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":820};
const content = `<path class="asdlnrbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:pencil" {...props}></Icon>
