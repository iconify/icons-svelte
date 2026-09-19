<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npl2v8x7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="npl2v8x7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mitten" {...props}></Icon>
