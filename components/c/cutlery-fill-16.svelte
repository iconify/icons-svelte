<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n358rvjyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n358rvjyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-fill-16" {...props}></Icon>
