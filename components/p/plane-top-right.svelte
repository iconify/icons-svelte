<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttut_pbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ttut_pbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plane-top-right" {...props}></Icon>
