<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siel51bpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siel51bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:composition-focus-square-bold" {...props}></Icon>
