<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp9lib0uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="rp9lib0uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-fill-16" {...props}></Icon>
