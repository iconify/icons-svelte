<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy_w0k1_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_w0k1_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-sharp" {...props}></Icon>
