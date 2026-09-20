<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx5jw_byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wx5jw_byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cover" {...props}></Icon>
