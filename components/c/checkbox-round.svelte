<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcu4ov-2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcu4ov-2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-round" {...props}></Icon>
