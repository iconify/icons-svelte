<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5_k3sbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z5_k3sbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-half-fill-20" {...props}></Icon>
