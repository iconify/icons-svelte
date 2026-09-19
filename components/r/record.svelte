<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci595pbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ci595pbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:record" {...props}></Icon>
