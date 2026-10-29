<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkljhobag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkljhobag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:code-solid" {...props}></Icon>
