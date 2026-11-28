<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4gxjhk3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z4gxjhk3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-duotone" {...props}></Icon>
