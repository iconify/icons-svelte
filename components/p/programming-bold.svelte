<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kok5zc6gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kok5zc6gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:programming-bold" {...props}></Icon>
