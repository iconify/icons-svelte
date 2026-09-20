<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-23vibek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-23vibek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cake-3-line" {...props}></Icon>
