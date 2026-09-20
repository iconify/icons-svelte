<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg6h5fb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg6h5fb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:plus-solid" {...props}></Icon>
