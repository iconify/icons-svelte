<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylkgs53ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylkgs53ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:loader-linear" {...props}></Icon>
