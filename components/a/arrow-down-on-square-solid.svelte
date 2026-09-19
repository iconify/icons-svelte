<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz17a-bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz17a-bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-on-square-solid" {...props}></Icon>
