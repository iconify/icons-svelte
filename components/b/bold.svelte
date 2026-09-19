<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mefe3absu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mefe3absu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bold" {...props}></Icon>
