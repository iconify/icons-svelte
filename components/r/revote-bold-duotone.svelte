<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/getfrabcc.css';
import '../../css/h/h99or5zfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="getfrabcc"/><path class="h99or5zfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:revote-bold-duotone" {...props}></Icon>
