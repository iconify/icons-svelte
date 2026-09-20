<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjtd81bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjtd81bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:color-invert-filled" {...props}></Icon>
