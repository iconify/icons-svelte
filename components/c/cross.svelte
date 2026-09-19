<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrk3srbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrk3srbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cross" {...props}></Icon>
