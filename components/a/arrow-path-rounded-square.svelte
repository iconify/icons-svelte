<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttrynm31t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttrynm31t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-path-rounded-square" {...props}></Icon>
