<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d14waibgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d14waibgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-upload-01" {...props}></Icon>
