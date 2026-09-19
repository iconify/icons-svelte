<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3fp4lb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k3fp4lb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:cut" {...props}></Icon>
