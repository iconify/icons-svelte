<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msl9otbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msl9otbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-library" {...props}></Icon>
