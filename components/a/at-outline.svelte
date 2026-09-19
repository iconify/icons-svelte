<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-06mqcpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-06mqcpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:at-outline" {...props}></Icon>
