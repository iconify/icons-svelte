<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-6dz7bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-6dz7bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:low-vision" {...props}></Icon>
