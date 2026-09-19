<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz3gffb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zz3gffb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:align-center" {...props}></Icon>
