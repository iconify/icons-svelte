<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvnxf2gox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnxf2gox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:band-aid-filled" {...props}></Icon>
