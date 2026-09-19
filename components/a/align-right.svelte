<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9-4knhbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9-4knhbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:align-right" {...props}></Icon>
