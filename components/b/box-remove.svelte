<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7-9zpbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x7-9zpbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:box-remove" {...props}></Icon>
