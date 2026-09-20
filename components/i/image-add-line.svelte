<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kko3h3bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kko3h3bui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:image-add-line" {...props}></Icon>
