<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue-h57b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue-h57b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:image-ai-filled" {...props}></Icon>
