<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k39ob-bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k39ob-bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fort-awesome-alt" {...props}></Icon>
