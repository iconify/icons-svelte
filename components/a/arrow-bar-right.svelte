<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldz_qwb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ldz_qwb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-bar-right" {...props}></Icon>
