<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d81wo4bpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d81wo4bpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-break-fill" {...props}></Icon>
