<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua1_gdcwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1_gdcwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paint-brush" {...props}></Icon>
