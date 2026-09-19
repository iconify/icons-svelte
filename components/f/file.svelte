<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8lqozphz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":512};
const content = `<path class="k8lqozphz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:file" {...props}></Icon>
