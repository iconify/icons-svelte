<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdeiysbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdeiysbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:edit-thin" {...props}></Icon>
