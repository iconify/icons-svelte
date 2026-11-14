<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-cg6y3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt-cg6y3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-remove" {...props}></Icon>
