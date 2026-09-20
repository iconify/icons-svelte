<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqo8ecpat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hqo8ecpat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-sampling" {...props}></Icon>
