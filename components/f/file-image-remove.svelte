<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ey-fprr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1ey-fprr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-remove" {...props}></Icon>
