<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9975k8sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p9975k8sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:box-3d-fill-16" {...props}></Icon>
