<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmc7v17rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmc7v17rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-off-filled" {...props}></Icon>
