<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t25i1-lkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t25i1-lkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-check-16-solid" {...props}></Icon>
