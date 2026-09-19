<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdo3n95-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wdo3n95-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-3-center-left-16-solid" {...props}></Icon>
