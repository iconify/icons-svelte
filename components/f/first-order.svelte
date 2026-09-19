<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zurw434pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="zurw434pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:first-order" {...props}></Icon>
