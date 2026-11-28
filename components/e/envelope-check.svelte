<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooww4mewa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ooww4mewa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:envelope-check" {...props}></Icon>
