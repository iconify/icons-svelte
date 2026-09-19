<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opip_vb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="opip_vb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:parking" {...props}></Icon>
