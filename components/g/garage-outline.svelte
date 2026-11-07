<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1a5gxbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l1a5gxbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:garage-outline" {...props}></Icon>
