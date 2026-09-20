<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb4ztpb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb4ztpb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pbr" {...props}></Icon>
