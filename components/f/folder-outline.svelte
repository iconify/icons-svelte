<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx5b0f8ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="tx5b0f8ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:folder-outline" {...props}></Icon>
