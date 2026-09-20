<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxw1kfb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxw1kfb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gitlab-solid" {...props}></Icon>
