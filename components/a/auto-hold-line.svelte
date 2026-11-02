<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbx4vpbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbx4vpbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:auto-hold-line" {...props}></Icon>
