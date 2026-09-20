<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1__tkbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1__tkbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-to-folder-bold" {...props}></Icon>
