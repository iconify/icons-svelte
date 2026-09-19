<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fle82wbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fle82wbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:plus" {...props}></Icon>
