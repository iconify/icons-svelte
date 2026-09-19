<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp4ci8xgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rp4ci8xgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:face-frown-16-solid" {...props}></Icon>
