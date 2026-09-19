<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyl68vb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dyl68vb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:align-right" {...props}></Icon>
