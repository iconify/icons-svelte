<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm654qbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mm654qbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-right" {...props}></Icon>
