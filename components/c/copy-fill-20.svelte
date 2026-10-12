<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5o0g-62r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d5o0g-62r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:copy-fill-20" {...props}></Icon>
